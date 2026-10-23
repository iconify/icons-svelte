<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96mxyb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h96mxyb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:house-plus" {...props}></Icon>
