<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_sl3b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iw_sl3b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-down2-filled" {...props}></Icon>
