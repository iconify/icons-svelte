<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s57ikubeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s57ikubeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:part" {...props}></Icon>
