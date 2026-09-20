<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9zj9mq8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o9zj9mq8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-under-height-restrictor" {...props}></Icon>
