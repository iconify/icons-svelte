<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcx6q5b0x.css';
import '../../css/k/k5lp20bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcx6q5b0x"/><path class="k5lp20bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ideon" {...props}></Icon>
