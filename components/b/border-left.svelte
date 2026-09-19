<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yssde8b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="yssde8b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-left" {...props}></Icon>
