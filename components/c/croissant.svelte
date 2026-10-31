<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us0u3x3yq.css';
import '../../css/i/i6wydjbva.css';
import '../../css/d/dk54v-gay.css';
import '../../css/s/s1ie28b-p.css';
import '../../css/f/fy4jxibwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="us0u3x3yq"/><path class="i6wydjbva"/><path class="dk54v-gay"/><path class="s1ie28b-p"/><path class="fy4jxibwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:croissant" {...props}></Icon>
