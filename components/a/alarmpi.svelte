<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o12gz742v.css';
import '../../css/s/sl76bhbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="o12gz742v"/><path class="sl76bhbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alarmpi" {...props}></Icon>
