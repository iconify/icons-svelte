<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5u1y60je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5u1y60je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airplane-seat-02" {...props}></Icon>
