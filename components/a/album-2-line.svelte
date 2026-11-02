<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nseds-b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nseds-b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:album-2-line" {...props}></Icon>
