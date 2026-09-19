<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrkl4_7zf.css';
import '../../css/p/pc8rfjy_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="zrkl4_7zf"/><path class="pc8rfjy_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nodejs" {...props}></Icon>
