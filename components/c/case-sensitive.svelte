<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggor3gbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggor3gbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:case-sensitive" {...props}></Icon>
