<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvh5-3bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tvh5-3bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:alt" {...props}></Icon>
