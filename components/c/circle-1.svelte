<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb9dmbc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb9dmbc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:circle-1" {...props}></Icon>
