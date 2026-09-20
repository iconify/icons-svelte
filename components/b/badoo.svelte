<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbv2_w84w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbv2_w84w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:badoo" {...props}></Icon>
