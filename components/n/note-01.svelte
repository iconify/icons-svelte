<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npvtwcljr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npvtwcljr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:note-01" {...props}></Icon>
