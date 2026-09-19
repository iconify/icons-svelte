<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk1dw34qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mk1dw34qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:polygon" {...props}></Icon>
