<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-h2_abdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-h2_abdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:erase-reverse-outline" {...props}></Icon>
