<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk_t0xb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zk_t0xb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:flip-vertical" {...props}></Icon>
