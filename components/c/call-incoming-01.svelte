<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu0fn4-yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wu0fn4-yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-incoming-01" {...props}></Icon>
