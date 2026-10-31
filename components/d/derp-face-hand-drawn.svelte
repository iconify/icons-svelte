<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1630-b4j.css';
import '../../css/g/g7u0urmpu.css';
import '../../css/b/ba10csb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="u1630-b4j"/><path clip-rule="evenodd" class="g7u0urmpu"/><path class="ba10csb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-memes:derp-face-hand-drawn" {...props}></Icon>
