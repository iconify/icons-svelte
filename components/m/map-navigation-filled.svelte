<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1u-aacmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1u-aacmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-navigation-filled" {...props}></Icon>
