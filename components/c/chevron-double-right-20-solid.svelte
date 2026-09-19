<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omg2h_xnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="omg2h_xnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-right-20-solid" {...props}></Icon>
