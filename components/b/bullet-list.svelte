<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znrxccwll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znrxccwll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bullet-list" {...props}></Icon>
