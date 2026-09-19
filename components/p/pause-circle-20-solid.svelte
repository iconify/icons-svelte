<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr5dqqb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xr5dqqb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pause-circle-20-solid" {...props}></Icon>
