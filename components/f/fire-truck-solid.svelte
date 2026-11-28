<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exkh_2n1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exkh_2n1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fire-truck-solid" {...props}></Icon>
