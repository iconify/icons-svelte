<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-u1sk9yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n-u1sk9yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:drizzle-orm" {...props}></Icon>
