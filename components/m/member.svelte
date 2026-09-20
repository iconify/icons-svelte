<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af72pmb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af72pmb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:member" {...props}></Icon>
