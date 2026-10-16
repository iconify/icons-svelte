<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz03-sdij.css';
import '../../css/a/ajbkkgb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lz03-sdij"/><path class="ajbkkgb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:money-bag-20" {...props}></Icon>
