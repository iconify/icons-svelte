<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjbr___sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vjbr___sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-raised-16-solid" {...props}></Icon>
