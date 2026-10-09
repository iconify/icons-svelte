<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juwx635fx.css';
import '../../css/y/yx8h1eeun.css';
import '../../css/y/yvxmkpbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="juwx635fx"/><path class="yx8h1eeun"/><path class="yvxmkpbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crystal-20" {...props}></Icon>
