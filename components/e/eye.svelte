<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xlhb4cbxr.css';
import '../../css/z/zoslq7bwc.css';
import '../../css/f/fd7qipbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xlhb4cbxr"/><path class="zoslq7bwc"/><path class="fd7qipbux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eye" {...props}></Icon>
