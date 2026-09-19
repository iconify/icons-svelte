<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnz306bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnz306bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:mining-filled" {...props}></Icon>
