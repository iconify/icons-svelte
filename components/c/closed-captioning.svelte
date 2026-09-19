<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izjwxlz8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izjwxlz8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:closed-captioning" {...props}></Icon>
