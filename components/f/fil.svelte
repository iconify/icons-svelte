<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw205fbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lw205fbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:fil" {...props}></Icon>
