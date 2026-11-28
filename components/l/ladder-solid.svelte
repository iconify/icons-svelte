<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_xvj8jaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_xvj8jaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ladder-solid" {...props}></Icon>
