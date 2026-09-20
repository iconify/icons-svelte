<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_-5cwb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-5cwb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drizzle-line" {...props}></Icon>
