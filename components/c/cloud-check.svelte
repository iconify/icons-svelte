<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6c9fmbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h6c9fmbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cloud-check" {...props}></Icon>
