<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt9zmbbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt9zmbbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plus-minus-times-divide" {...props}></Icon>
