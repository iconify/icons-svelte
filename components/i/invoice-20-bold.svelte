<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ps03s-o.css';
import '../../css/i/iz1dmwoac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y9ps03s-o"/><path class="iz1dmwoac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:invoice-20-bold" {...props}></Icon>
