<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8-zfaccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8-zfaccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:home-alt-slim" {...props}></Icon>
