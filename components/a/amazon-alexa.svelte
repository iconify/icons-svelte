<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abx1n4ozg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abx1n4ozg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:amazon-alexa" {...props}></Icon>
