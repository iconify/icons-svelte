<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0_jigb-j.css';
import '../../css/x/xjr5jrboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0_jigb-j"/><path class="xjr5jrboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:radio" {...props}></Icon>
