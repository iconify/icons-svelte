<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg-5y4bmb.css';
import '../../css/p/pv1m9o-dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cg-5y4bmb"/><path class="pv1m9o-dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:comments" {...props}></Icon>
