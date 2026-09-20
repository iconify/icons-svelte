<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmj9r3-wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmj9r3-wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-3-fill" {...props}></Icon>
