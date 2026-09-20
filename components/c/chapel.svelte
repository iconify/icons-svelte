<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6y7mcc8q.css';
import '../../css/l/lc0gopbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="l6y7mcc8q"/><path class="lc0gopbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:chapel" {...props}></Icon>
