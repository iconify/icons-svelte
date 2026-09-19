<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qetnckbkp.css';
import '../../css/y/yr13g5spn.css';
import '../../css/d/d_cckzeas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qetnckbkp"/><path class="yr13g5spn"/><path class="d_cckzeas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mountfuji" {...props}></Icon>
