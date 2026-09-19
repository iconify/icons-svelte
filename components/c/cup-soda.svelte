<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/ja_r16b-t.css';
import '../../css/h/hbxhkzysn.css';
import '../../css/z/zit5rebxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ja_r16b-t"/><path class="hbxhkzysn"/><path class="zit5rebxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cup-soda" {...props}></Icon>
