<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjc_5qbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjc_5qbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt-disscount-filled" {...props}></Icon>
