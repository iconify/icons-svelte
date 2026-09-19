<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gum_hnbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gum_hnbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:blog" {...props}></Icon>
