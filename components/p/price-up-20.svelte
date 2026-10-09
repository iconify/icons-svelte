<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lae2_dgov.css';
import '../../css/z/znm6bw41g.css';
import '../../css/i/iiq2hgbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lae2_dgov"/><path class="znm6bw41g"/><path class="iiq2hgbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-up-20" {...props}></Icon>
