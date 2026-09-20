<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaa5_5o5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaa5_5o5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bong-off" {...props}></Icon>
