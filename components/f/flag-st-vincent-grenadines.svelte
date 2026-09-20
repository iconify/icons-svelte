<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpth-wqs.css';
import '../../css/p/pi7jdd7uf.css';
import '../../css/e/ez5131brf.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="pi7jdd7uf"/><path class="ez5131brf"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-st-vincent-grenadines" {...props}></Icon>
