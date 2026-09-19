<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh74urp9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh74urp9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:lactation-outline-24px" {...props}></Icon>
