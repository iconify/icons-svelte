<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weg5p8w9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weg5p8w9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dam-line" {...props}></Icon>
