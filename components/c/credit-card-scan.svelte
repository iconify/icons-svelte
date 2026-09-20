<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs6y6vbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs6y6vbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:credit-card-scan" {...props}></Icon>
