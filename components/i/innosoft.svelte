<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_bbn7bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="f_bbn7bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:innosoft" {...props}></Icon>
