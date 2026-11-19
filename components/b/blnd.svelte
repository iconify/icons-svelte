<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esc2lymja.css';
import '../../css/n/nn1p_hz4s.css';
import '../../css/w/w30ikw3fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esc2lymja"/><path class="nn1p_hz4s"/><path class="w30ikw3fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:blnd" {...props}></Icon>
