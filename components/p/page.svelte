<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw-pbdcck.css';
import '../../css/u/ucdp9ybuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pw-pbdcck"/><path class="ucdp9ybuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:page" {...props}></Icon>
