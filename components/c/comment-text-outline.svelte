<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm2rwgc2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm2rwgc2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-text-outline" {...props}></Icon>
