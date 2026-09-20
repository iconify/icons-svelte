<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7zqifb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7zqifb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:certificate-2-line" {...props}></Icon>
