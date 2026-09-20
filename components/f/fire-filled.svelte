<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv1__2_yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv1__2_yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fire-filled" {...props}></Icon>
