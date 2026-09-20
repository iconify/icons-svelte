<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teneazb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="teneazb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:balance-scale-left" {...props}></Icon>
