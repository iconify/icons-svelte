<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvw6d3hwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvw6d3hwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:moon-solid" {...props}></Icon>
