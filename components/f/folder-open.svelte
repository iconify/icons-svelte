<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f7--fccjq.css';
import '../../css/z/z791spbav.css';
import '../../css/b/b9jcm8g0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f7--fccjq"/><path class="z791spbav"/><path class="b9jcm8g0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-open" {...props}></Icon>
