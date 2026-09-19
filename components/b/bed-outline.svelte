<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe9tqcc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe9tqcc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bed-outline" {...props}></Icon>
