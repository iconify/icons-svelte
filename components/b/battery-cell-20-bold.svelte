<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xffij3b0b.css';
import '../../css/s/ss7z2mb1x.css';
import '../../css/n/nqi7nq_zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xffij3b0b"/><path class="ss7z2mb1x"/><path class="nqi7nq_zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-cell-20-bold" {...props}></Icon>
