<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji4dstbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ji4dstbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:align-pull-left" {...props}></Icon>
