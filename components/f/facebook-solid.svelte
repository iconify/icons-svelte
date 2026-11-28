<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrp280b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrp280b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:facebook-solid" {...props}></Icon>
