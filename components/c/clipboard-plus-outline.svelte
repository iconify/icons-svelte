<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b40zu7uku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b40zu7uku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-plus-outline" {...props}></Icon>
