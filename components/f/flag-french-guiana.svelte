<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpth-wqs.css';
import '../../css/a/au2uu7bci.css';
import '../../css/p/pcc9ye47b.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wcpth-wqs"/><path class="au2uu7bci"/><path class="pcc9ye47b"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-french-guiana" {...props}></Icon>
