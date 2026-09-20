<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzlfy1tml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzlfy1tml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nest" {...props}></Icon>
