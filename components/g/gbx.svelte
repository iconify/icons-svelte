<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwhjj7i3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dwhjj7i3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:gbx" {...props}></Icon>
