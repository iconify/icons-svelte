<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly8ue0hvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly8ue0hvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gumtree" {...props}></Icon>
