<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcuc6fbtx.css';
import '../../css/t/tr1yy1b0h.css';
import '../../css/a/ao630jb1n.css';
import '../../css/j/j5p651bbv.css';
import '../../css/b/b2vpz7b9s.css';
import '../../css/u/umdyk_b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rcuc6fbtx"/><path class="tr1yy1b0h"/><path class="ao630jb1n"/><path class="j5p651bbv"/><path class="b2vpz7b9s"/><path class="umdyk_b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-bike-20-bold" {...props}></Icon>
