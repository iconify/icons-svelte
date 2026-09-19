<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trcsivmik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trcsivmik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-right-square-filled" {...props}></Icon>
