<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7j09yb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":520};
const content = `<path class="l7j09yb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:branch" {...props}></Icon>
