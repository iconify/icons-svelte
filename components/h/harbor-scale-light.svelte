<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw55blb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hw55blb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:harbor-scale-light" {...props}></Icon>
