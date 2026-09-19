<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgalcwsyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgalcwsyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flask-round-filled" {...props}></Icon>
