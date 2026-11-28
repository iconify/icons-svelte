<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osmynbc3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osmynbc3o primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pentagon-dashed-duotone" {...props}></Icon>
