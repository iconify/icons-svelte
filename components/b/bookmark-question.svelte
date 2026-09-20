<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxnwnf76c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxnwnf76c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-question" {...props}></Icon>
