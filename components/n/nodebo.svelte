<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbozhdcpj.css';
import '../../css/s/sb-7x_b3r.css';
import '../../css/f/fzmbfkb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":120,"height":120};
const content = `<g class="zbozhdcpj"><circle class="sb-7x_b3r"/><path class="fzmbfkb6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nodebo" {...props}></Icon>
