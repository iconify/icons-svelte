<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y47zebiup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y47zebiup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-3-square-bold" {...props}></Icon>
