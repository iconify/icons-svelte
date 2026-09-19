<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht65-g-1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ht65-g-1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:next-js" {...props}></Icon>
