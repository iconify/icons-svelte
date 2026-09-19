<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzwd2419d.css';
import '../../css/q/q-i98cb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lzwd2419d"/><path class="q-i98cb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:circle-left" {...props}></Icon>
