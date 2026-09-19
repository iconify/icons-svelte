<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlgozrxrt.css';
import '../../css/h/hztm1ryfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlgozrxrt"/><path class="hztm1ryfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heart-square" {...props}></Icon>
