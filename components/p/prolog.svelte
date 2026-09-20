<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx8hrybbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wx8hrybbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:prolog" {...props}></Icon>
