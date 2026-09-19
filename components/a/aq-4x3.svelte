<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgfnrcc8l.css';
import '../../css/u/uce-6cv7i.css';
import '../../css/x/xjsfynbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="vgfnrcc8l"/><path class="uce-6cv7i"/><path transform="scale(.86021 .96774)" class="xjsfynbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:aq-4x3" {...props}></Icon>
