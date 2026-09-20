<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq6logb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tq6logb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beszel-dark" {...props}></Icon>
