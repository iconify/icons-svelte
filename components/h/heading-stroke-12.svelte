<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltq5cfbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ltq5cfbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heading-stroke-12" {...props}></Icon>
