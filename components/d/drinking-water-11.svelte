<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh_sznb5z.css';
import '../../css/z/zz6yhdbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="kh_sznb5z"/><path class="zz6yhdbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:drinking-water-11" {...props}></Icon>
