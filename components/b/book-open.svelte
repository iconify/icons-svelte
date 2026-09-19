<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuoeu1bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuoeu1bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:book-open" {...props}></Icon>
