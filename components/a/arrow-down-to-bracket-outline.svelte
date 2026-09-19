<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj-nilb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj-nilb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:arrow-down-to-bracket-outline" {...props}></Icon>
