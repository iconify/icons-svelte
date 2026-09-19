<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzx5i9bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzx5i9bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:j" {...props}></Icon>
