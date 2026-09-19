<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k73w4j2dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k73w4j2dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:brush" {...props}></Icon>
