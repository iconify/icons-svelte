<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkdo0pbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkdo0pbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-check-solid" {...props}></Icon>
