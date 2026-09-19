<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx3fcibph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx3fcibph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cloud-download" {...props}></Icon>
