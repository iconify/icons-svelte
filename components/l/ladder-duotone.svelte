<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqtnr_bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vqtnr_bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ladder-duotone" {...props}></Icon>
