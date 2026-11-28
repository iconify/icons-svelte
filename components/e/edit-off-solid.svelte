<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys95-wbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys95-wbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:edit-off-solid" {...props}></Icon>
