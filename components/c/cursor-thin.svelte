<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxg9tc2er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxg9tc2er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cursor-thin" {...props}></Icon>
