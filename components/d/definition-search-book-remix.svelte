<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk68a97yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk68a97yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:definition-search-book-remix" {...props}></Icon>
