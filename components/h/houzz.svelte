<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_bvr4aji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_bvr4aji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:houzz" {...props}></Icon>
