<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5vw760we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5vw760we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-down" {...props}></Icon>
