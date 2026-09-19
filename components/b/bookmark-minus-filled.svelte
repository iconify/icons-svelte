<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpe3d1buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpe3d1buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bookmark-minus-filled" {...props}></Icon>
