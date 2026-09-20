<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzzfaoeme.css';
import '../../css/n/n9kcvmbeu.css';
import '../../css/p/p5lazdb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bzzfaoeme"/><path class="n9kcvmbeu"/><path class="p5lazdb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-map" {...props}></Icon>
