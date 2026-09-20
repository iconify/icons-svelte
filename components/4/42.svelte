<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd52asfew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd52asfew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:42" {...props}></Icon>
