<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by92osboh.css';
import '../../css/b/bt7ducbtn.css';
import '../../css/o/ops1169qo.css';
import '../../css/e/ew-rlnbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="by92osboh"/><path class="bt7ducbtn"/><path class="ops1169qo"/><path class="ew-rlnbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coral-48" {...props}></Icon>
