<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtpb7vbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtpb7vbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-tongue" {...props}></Icon>
