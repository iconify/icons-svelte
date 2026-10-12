<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx95jbbja.css';
import '../../css/x/xcxa9bb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kx95jbbja"/><path class="xcxa9bb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:rocket-fill-20" {...props}></Icon>
