<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqw21yb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="oqw21yb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-up-right" {...props}></Icon>
