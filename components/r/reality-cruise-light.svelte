<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfjwpjbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfjwpjbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reality-cruise-light" {...props}></Icon>
