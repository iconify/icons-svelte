<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzl56ybjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzl56ybjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:music-2-gloss" {...props}></Icon>
