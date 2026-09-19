<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igt4slb-u.css';
import '../../css/r/rfo4zzbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igt4slb-u"/><path class="rfo4zzbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-square-half-filled" {...props}></Icon>
