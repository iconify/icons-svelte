<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyk7swgfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyk7swgfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:plus-circle" {...props}></Icon>
