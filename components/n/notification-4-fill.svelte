<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsb31n2fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsb31n2fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-4-fill" {...props}></Icon>
