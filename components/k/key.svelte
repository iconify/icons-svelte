<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwdcyfbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwdcyfbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:key" {...props}></Icon>
