<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6c2uebib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a6c2uebib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:brick-wall-with-battlement-and-sallyport" {...props}></Icon>
