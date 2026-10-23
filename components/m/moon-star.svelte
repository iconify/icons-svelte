<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwexfcbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwexfcbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:moon-star" {...props}></Icon>
