<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blkkphbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="blkkphbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:definition-search-book-remix" {...props}></Icon>
