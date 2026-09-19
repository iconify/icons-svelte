<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/str33hb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="str33hb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:modify-poly" {...props}></Icon>
