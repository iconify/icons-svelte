<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezaos2o-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ezaos2o-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:folder-minus" {...props}></Icon>
