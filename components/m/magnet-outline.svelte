<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zllmftbax.css';
import '../../css/k/kot2fq0bc.css';
import '../../css/a/a4kaplbpc.css';
import '../../css/k/k2rcg5b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zllmftbax"/><path class="kot2fq0bc"/><path class="a4kaplbpc"/><path class="k2rcg5b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:magnet-outline" {...props}></Icon>
