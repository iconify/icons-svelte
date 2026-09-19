<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7ithy0ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7ithy0ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dom" {...props}></Icon>
