<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6ve9rbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6ve9rbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remix-line" {...props}></Icon>
