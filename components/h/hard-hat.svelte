<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxk1z3lyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxk1z3lyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:hard-hat" {...props}></Icon>
