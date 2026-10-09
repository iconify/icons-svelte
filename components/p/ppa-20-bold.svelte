<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ps03s-o.css';
import '../../css/z/zabzdf0zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y9ps03s-o"/><path class="zabzdf0zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-20-bold" {...props}></Icon>
