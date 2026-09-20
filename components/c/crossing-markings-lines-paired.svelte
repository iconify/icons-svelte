<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv2s_thge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kv2s_thge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crossing-markings-lines-paired" {...props}></Icon>
