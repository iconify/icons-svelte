<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wedi3hbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wedi3hbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:carrot-gloss" {...props}></Icon>
