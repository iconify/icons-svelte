<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytw07_b-i.css';
import '../../css/v/vh7f-ub8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ytw07_b-i"/><path class="vh7f-ub8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bikini" {...props}></Icon>
