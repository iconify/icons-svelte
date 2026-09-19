<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dop_v-6bo.css';
import '../../css/q/qcna4wjtc.css';
import '../../css/c/ct7l-y_5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dop_v-6bo"/><path class="qcna4wjtc"/><path class="ct7l-y_5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:filefolder" {...props}></Icon>
