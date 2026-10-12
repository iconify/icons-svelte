<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfebi87jj.css';
import '../../css/x/x52zq4crp.css';
import '../../css/j/jqbyuib6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cfebi87jj"/><path class="x52zq4crp"/><path class="jqbyuib6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-key-stroke-20" {...props}></Icon>
