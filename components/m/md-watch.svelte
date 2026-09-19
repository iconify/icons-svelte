<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib3rsc9pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib3rsc9pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-watch" {...props}></Icon>
