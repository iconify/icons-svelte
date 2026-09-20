<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-sctmise.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-sctmise"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-snooze-line" {...props}></Icon>
