<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9lx1ccvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9lx1ccvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:needle" {...props}></Icon>
