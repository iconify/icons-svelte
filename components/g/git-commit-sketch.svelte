<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o5leul9ao.css';
import '../../css/p/p4bxscbjk.css';
import '../../css/z/zuqzax3uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o5leul9ao"/><path class="p4bxscbjk"/><path class="zuqzax3uu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-commit-sketch" {...props}></Icon>
