<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp7rqpw6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sp7rqpw6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rotate-clockwise-alt" {...props}></Icon>
