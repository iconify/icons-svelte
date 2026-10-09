<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmpt51hmn.css';
import '../../css/z/zfhxusean.css';
import '../../css/y/y-rk38d9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jmpt51hmn"/><path class="zfhxusean"/><path class="y-rk38d9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ore-20-bold" {...props}></Icon>
