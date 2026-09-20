<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xunhhwbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xunhhwbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:link" {...props}></Icon>
