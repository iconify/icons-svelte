<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz1y3cc3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":489,"height":628};
const content = `<path class="fz1y3cc3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:back" {...props}></Icon>
