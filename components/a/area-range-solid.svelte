<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tusap453n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tusap453n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:area-range-solid" {...props}></Icon>
