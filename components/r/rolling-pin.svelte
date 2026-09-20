<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-78w7_bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-78w7_bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rolling-pin" {...props}></Icon>
