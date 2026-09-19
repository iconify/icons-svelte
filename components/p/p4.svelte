<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liaffxq7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="liaffxq7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:p4" {...props}></Icon>
