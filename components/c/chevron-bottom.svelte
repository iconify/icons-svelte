<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd24wbb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sd24wbb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:chevron-bottom" {...props}></Icon>
