<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftsci7nex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftsci7nex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:meetone" {...props}></Icon>
