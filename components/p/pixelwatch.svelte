<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zum8yl33q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zum8yl33q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pixelwatch" {...props}></Icon>
