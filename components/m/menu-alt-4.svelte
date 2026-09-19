<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6amuwb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6amuwb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:menu-alt-4" {...props}></Icon>
