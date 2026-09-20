<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z12loqhsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z12loqhsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cradle-outline" {...props}></Icon>
