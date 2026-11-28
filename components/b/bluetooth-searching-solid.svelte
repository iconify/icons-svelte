<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd-3_xxsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd-3_xxsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bluetooth-searching-solid" {...props}></Icon>
