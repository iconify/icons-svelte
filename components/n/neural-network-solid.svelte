<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_n0vpbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_n0vpbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:neural-network-solid" {...props}></Icon>
