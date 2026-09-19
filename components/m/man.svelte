<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajgcukb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajgcukb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:man" {...props}></Icon>
