<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lntrp4opm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lntrp4opm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:lock-keyhole-filled" {...props}></Icon>
