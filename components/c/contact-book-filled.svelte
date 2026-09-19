<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7u6qacet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7u6qacet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:contact-book-filled" {...props}></Icon>
