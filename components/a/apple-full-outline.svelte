<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waoq3bcbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waoq3bcbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:apple-full-outline" {...props}></Icon>
