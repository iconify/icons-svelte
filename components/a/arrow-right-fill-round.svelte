<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4559ebmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4559ebmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-fill-round" {...props}></Icon>
