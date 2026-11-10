<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfregu8ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xfregu8ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-plus-20-solid" {...props}></Icon>
