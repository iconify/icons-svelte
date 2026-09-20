<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cff26lznd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cff26lznd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:map-search-remix" {...props}></Icon>
