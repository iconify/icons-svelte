<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2sr0symm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f2sr0symm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:extent" {...props}></Icon>
