<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn0esybxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn0esybxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:b2m" {...props}></Icon>
