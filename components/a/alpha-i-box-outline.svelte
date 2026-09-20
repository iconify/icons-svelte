<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya2p9ecfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ya2p9ecfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-i-box-outline" {...props}></Icon>
