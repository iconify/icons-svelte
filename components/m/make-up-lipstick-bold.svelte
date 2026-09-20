<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwv-ctbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwv-ctbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:make-up-lipstick-bold" {...props}></Icon>
