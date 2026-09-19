<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpgm48bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bpgm48bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:clapperboard" {...props}></Icon>
