<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e75f81i5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":479,"height":512};
const content = `<path class="e75f81i5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:progress" {...props}></Icon>
