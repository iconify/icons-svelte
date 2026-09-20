<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgpnn41og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgpnn41og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcases-line" {...props}></Icon>
