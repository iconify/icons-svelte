<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do--7v-3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="do--7v-3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:layers-outline" {...props}></Icon>
