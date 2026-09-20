<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gztry8buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gztry8buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bubble-filled" {...props}></Icon>
