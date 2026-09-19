<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-j0m6bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-j0m6bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:moon" {...props}></Icon>
