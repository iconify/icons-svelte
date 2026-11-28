<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajj45qbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajj45qbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:inbox-arrow-down" {...props}></Icon>
