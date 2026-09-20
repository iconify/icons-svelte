<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so9w1vbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so9w1vbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lrc" {...props}></Icon>
