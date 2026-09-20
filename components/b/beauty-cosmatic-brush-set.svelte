<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi01502br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wi01502br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-cosmatic-brush-set" {...props}></Icon>
