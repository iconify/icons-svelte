<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p95ko6b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p95ko6b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pear" {...props}></Icon>
