<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2c97abxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2c97abxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:headphone-alt-filled" {...props}></Icon>
