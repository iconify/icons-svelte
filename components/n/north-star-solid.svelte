<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgumd2yhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgumd2yhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:north-star-solid" {...props}></Icon>
