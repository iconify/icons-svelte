<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzf1cfrqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzf1cfrqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fiverr" {...props}></Icon>
