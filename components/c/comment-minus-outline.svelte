<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqxir0bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqxir0bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-minus-outline" {...props}></Icon>
