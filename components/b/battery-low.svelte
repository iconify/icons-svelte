<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w71h-cbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w71h-cbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:battery-low" {...props}></Icon>
