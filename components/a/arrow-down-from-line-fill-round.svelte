<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc0tz1cqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0tz1cqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-from-line-fill-round" {...props}></Icon>
