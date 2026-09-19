<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmbggnbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pmbggnbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:lrc" {...props}></Icon>
