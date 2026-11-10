<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3ikzu8te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m3ikzu8te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-x-mark-20-solid" {...props}></Icon>
