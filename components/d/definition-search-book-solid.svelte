<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_1ur7b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g_1ur7b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:definition-search-book-solid" {...props}></Icon>
