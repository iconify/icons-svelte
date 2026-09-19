<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3cv_cc6k.css';
import '../../css/j/jaih09bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3cv_cc6k"/><path class="jaih09bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:power-standby" {...props}></Icon>
