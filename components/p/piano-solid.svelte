<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfbk5nxgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfbk5nxgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:piano-solid" {...props}></Icon>
