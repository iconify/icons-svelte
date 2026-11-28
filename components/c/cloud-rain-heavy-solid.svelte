<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa60ncbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa60ncbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-rain-heavy-solid" {...props}></Icon>
