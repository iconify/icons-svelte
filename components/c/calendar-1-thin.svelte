<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bucw1rb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bucw1rb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-1-thin" {...props}></Icon>
