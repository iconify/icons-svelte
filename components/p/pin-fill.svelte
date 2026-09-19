<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikcfa0bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ikcfa0bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:pin-fill" {...props}></Icon>
