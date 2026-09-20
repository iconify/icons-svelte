<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh7bcpbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7bcpbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paper-plane-filled" {...props}></Icon>
