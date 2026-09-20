<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpcolwbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpcolwbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lab-tube" {...props}></Icon>
