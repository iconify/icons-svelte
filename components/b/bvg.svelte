<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ervrb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7ervrb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bvg" {...props}></Icon>
