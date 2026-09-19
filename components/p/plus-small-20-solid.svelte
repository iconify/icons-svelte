<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_hkppbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gv_hkppbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:plus-small-20-solid" {...props}></Icon>
