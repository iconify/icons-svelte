<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt7-flo0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zt7-flo0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-americas-16-solid" {...props}></Icon>
