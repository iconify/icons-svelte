<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlxms-bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlxms-bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-lightning-rain-solid" {...props}></Icon>
