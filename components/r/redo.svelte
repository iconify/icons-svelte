<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu_9tcoym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":384};
const content = `<path class="eu_9tcoym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:redo" {...props}></Icon>
