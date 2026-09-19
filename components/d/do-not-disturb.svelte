<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8550rb9o.css';
import '../../css/d/dvr3kccns.css';
import '../../css/z/z3s59cbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":24};
const content = `<path class="x8550rb9o"/><path class="dvr3kccns"/><path class="z3s59cbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:do-not-disturb" {...props}></Icon>
