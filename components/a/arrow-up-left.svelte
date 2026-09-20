<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td599z-9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td599z-9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-left" {...props}></Icon>
