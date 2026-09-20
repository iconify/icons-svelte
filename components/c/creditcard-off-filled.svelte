<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5_gckbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5_gckbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:creditcard-off-filled" {...props}></Icon>
