<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg6nrp1ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":608,"height":1280};
const content = `<path class="rg6nrp1ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angle-left" {...props}></Icon>
