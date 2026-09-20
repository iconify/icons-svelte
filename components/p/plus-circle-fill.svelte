<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la-8--b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="la-8--b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:plus-circle-fill" {...props}></Icon>
