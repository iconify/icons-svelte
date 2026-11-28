<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtv1suskr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtv1suskr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:banana-solid" {...props}></Icon>
