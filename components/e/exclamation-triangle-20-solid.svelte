<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpx34h5gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kpx34h5gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:exclamation-triangle-20-solid" {...props}></Icon>
