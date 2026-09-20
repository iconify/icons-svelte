<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g60a0jb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g60a0jb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-cog-outline" {...props}></Icon>
