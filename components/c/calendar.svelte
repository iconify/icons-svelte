<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxb6bgbsy.css';
import '../../css/t/tyb07sbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="gxb6bgbsy"/><path class="tyb07sbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:calendar" {...props}></Icon>
