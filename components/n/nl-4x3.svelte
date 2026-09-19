<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc3doybli.css';
import '../../css/v/v18c9fbau.css';
import '../../css/z/zzkm3r1nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="lc3doybli"/><path class="v18c9fbau"/><path class="zzkm3r1nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:nl-4x3" {...props}></Icon>
