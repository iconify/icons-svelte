<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei7oqkbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei7oqkbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:book-bookmark" {...props}></Icon>
