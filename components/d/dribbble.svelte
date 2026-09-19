<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urgz1kfox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urgz1kfox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dribbble" {...props}></Icon>
