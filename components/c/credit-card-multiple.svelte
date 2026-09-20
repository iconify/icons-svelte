<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mor6mhbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mor6mhbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-multiple" {...props}></Icon>
