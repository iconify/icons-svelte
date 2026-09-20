<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uipgvcbdd.css';
import '../../css/c/cpiyk6e9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":259};
const content = `<path class="uipgvcbdd"/><path class="cpiyk6e9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pandacss" {...props}></Icon>
