<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsr9xtben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hsr9xtben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:language-16-solid" {...props}></Icon>
