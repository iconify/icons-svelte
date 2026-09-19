<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn95y1o2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jn95y1o2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-4-square-fill" {...props}></Icon>
