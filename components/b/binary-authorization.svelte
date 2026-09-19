<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e50c8gb5g.css';
import '../../css/u/ut5kjkb9c.css';
import '../../css/m/mry1nj2og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e50c8gb5g"/><path class="ut5kjkb9c"/><path class="mry1nj2og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:binary-authorization" {...props}></Icon>
