<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2q536p7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="w2q536p7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-down-right" {...props}></Icon>
