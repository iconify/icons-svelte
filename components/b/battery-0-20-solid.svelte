<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0-afgbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y0-afgbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-0-20-solid" {...props}></Icon>
