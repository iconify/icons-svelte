<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahns1ub3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ahns1ub3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:biorxiv-square" {...props}></Icon>
