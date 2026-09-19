<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn-ttlbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tn-ttlbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:lightbulb" {...props}></Icon>
