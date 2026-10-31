<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp40r6auq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp40r6auq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:laser" {...props}></Icon>
