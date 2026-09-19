<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jowakrblr.css';
import '../../css/t/t2r34r-uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jowakrblr"/><path class="t2r34r-uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:octopus" {...props}></Icon>
