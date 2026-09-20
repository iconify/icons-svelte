<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqpy7rbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tqpy7rbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-text-single-line" {...props}></Icon>
