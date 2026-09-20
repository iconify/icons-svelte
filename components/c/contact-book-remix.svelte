<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1-n18b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i1-n18b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:contact-book-remix" {...props}></Icon>
