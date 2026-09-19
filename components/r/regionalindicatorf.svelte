<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbd350alm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lbd350alm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatorf" {...props}></Icon>
