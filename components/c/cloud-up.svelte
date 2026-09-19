<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvu7ot9vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="vvu7ot9vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cloud-up" {...props}></Icon>
