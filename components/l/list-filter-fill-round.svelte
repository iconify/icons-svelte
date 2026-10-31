<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m538sebkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m538sebkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-filter-fill-round" {...props}></Icon>
