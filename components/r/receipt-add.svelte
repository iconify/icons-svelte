<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm_fa0dyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_fa0dyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:receipt-add" {...props}></Icon>
