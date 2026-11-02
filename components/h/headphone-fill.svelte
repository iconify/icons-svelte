<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7jzhi2jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7jzhi2jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:headphone-fill" {...props}></Icon>
