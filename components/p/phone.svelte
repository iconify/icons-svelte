<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr7htobqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="hr7htobqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:phone" {...props}></Icon>
