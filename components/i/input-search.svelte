<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbzeg4b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbzeg4b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:input-search" {...props}></Icon>
