<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvh0w_r3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vvh0w_r3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-exclamation-20-solid" {...props}></Icon>
