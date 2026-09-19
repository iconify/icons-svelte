<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtwzdjb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mtwzdjb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-quote" {...props}></Icon>
