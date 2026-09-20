<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-l3fcbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-l3fcbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:relay" {...props}></Icon>
