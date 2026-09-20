<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq195u44k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eq195u44k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:r-16" {...props}></Icon>
