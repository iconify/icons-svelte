<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ffw2qjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6ffw2qjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-dots" {...props}></Icon>
