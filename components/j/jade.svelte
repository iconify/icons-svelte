<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwqm53jlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwqm53jlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jade" {...props}></Icon>
