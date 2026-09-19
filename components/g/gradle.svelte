<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqv0ml9jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqv0ml9jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gradle" {...props}></Icon>
