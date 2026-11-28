<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuf_yac1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wuf_yac1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dumbbell-duotone" {...props}></Icon>
