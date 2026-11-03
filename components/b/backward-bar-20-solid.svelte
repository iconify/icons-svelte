<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xawstirwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xawstirwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:backward-bar-20-solid" {...props}></Icon>
