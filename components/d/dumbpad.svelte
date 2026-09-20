<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9_1ckzyh.css';
import '../../css/z/zo4u7dbqx.css';
import '../../css/e/egb1_lbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="h9_1ckzyh"/><path class="zo4u7dbqx"/><path class="egb1_lbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbpad" {...props}></Icon>
