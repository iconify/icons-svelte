<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu6r7n82p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="xu6r7n82p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:daft-punk" {...props}></Icon>
