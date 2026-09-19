<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpfalebwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fpfalebwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chevron-thin-up" {...props}></Icon>
