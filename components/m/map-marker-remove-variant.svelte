<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls6txntpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls6txntpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-remove-variant" {...props}></Icon>
