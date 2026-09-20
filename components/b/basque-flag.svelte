<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8cxt48ie.css';
import '../../css/m/mqp8nib7i.css';
import '../../css/x/xfcr-jbja.css';
import '../../css/m/m-swk2bsf.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="mqp8nib7i"/><path class="xfcr-jbja"/><path class="m-swk2bsf"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:basque-flag" {...props}></Icon>
