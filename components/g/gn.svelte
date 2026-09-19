<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylhcwq4-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ylhcwq4-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gn" {...props}></Icon>
