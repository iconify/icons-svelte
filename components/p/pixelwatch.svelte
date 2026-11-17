<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6i7srb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6i7srb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pixelwatch" {...props}></Icon>
