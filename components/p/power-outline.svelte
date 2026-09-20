<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlwsij6us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlwsij6us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:power-outline" {...props}></Icon>
