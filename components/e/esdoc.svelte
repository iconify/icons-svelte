<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocxwenq6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ocxwenq6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:esdoc" {...props}></Icon>
