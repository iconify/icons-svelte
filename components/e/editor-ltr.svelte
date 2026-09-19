<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq-2l-tup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cq-2l-tup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-ltr" {...props}></Icon>
