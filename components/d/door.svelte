<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7l9mq-pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d7l9mq-pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:door" {...props}></Icon>
