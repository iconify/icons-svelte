<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtxw53bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtxw53bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:network-lock" {...props}></Icon>
