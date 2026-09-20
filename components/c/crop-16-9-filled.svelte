<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rns8vj0tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rns8vj0tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-16-9-filled" {...props}></Icon>
