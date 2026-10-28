<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzx3jgbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzx3jgbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nostos-light" {...props}></Icon>
