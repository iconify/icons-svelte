<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_q0t1ebv.css';
import '../../css/o/o5xttwudf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_q0t1ebv"/><path class="o5xttwudf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notepad-plus-plus-light" {...props}></Icon>
