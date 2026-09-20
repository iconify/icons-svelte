<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnt2txbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnt2txbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:close-circle-filled" {...props}></Icon>
