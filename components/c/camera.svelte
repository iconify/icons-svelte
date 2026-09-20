<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syqfetb6n.css';
import '../../css/l/lkky-nhlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="syqfetb6n"/><path class="lkky-nhlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:camera" {...props}></Icon>
