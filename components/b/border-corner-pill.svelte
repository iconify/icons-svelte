<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_5j7i_8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_5j7i_8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-corner-pill" {...props}></Icon>
