<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z56mahxkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z56mahxkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lamp-fill-round" {...props}></Icon>
