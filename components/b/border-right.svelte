<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8o1xhse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ar8o1xhse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-right" {...props}></Icon>
