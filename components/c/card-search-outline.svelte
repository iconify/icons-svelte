<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9_q2hzyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9_q2hzyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-search-outline" {...props}></Icon>
