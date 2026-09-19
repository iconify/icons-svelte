<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6hh-zbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c6hh-zbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-live" {...props}></Icon>
