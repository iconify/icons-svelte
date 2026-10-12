<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6rvu93np.css';
import '../../css/y/yu2pl9xbr.css';
import '../../css/z/z_aw5vbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n6rvu93np"/><path class="yu2pl9xbr"/><path class="z_aw5vbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-lock-20" {...props}></Icon>
