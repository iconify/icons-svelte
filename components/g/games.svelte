<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no85bgsgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="no85bgsgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:games" {...props}></Icon>
