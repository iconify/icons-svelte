<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7aadjbad.css';
import '../../css/l/lthy19bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d7aadjbad"/><path class="lthy19bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paw-20-bold" {...props}></Icon>
