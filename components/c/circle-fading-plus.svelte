<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faibrnbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faibrnbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-fading-plus" {...props}></Icon>
