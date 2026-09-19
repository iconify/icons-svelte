<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngw-7mbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngw-7mbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:adjustments-vertical-outline" {...props}></Icon>
