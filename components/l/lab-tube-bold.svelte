<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1n_cvbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1n_cvbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lab-tube-bold" {...props}></Icon>
