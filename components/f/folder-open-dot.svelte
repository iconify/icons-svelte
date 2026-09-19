<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yb5rymbwe.css';
import '../../css/n/ncssx-uto.css';
import '../../css/f/ffdsudbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yb5rymbwe"/><path class="ncssx-uto"/><path class="ffdsudbxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-open-dot" {...props}></Icon>
