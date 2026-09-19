<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4kr70i4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="l4kr70i4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:price" {...props}></Icon>
