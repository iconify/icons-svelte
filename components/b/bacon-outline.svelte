<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-033rbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-033rbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bacon-outline" {...props}></Icon>
