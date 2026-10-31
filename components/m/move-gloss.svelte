<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0ake9b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0ake9b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:move-gloss" {...props}></Icon>
