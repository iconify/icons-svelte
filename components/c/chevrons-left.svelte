<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke3m0vsct.css';
import '../../css/j/jfaet3x_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke3m0vsct"/><path class="jfaet3x_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevrons-left" {...props}></Icon>
