<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b137xabqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b137xabqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:badge" {...props}></Icon>
