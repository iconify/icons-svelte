<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul01t7oem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ul01t7oem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:kirby" {...props}></Icon>
