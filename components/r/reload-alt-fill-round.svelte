<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gea0704lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gea0704lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reload-alt-fill-round" {...props}></Icon>
