<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8wc5t8ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="g8wc5t8ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:chevron-left" {...props}></Icon>
