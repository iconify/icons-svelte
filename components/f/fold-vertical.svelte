<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyi43iblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyi43iblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:fold-vertical" {...props}></Icon>
