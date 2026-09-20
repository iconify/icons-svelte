<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyfts8-ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyfts8-ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-serif-circle-outline" {...props}></Icon>
