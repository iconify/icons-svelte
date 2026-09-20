<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch_f8mbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch_f8mbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:open3d" {...props}></Icon>
