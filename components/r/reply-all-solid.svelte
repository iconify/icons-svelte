<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btcv4zsiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btcv4zsiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:reply-all-solid" {...props}></Icon>
