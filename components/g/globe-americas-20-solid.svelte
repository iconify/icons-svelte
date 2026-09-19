<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovyp-kbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ovyp-kbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-americas-20-solid" {...props}></Icon>
