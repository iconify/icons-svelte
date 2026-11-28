<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrt-b3b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrt-b3b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-plus" {...props}></Icon>
