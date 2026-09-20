<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po44rxx7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="po44rxx7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-double-20-solid" {...props}></Icon>
