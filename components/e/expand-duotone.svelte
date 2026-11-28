<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ardmbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y1ardmbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:expand-duotone" {...props}></Icon>
