<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz_e4bjlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz_e4bjlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:angle-left" {...props}></Icon>
