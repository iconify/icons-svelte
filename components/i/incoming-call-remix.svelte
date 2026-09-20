<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npp3zoi_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="npp3zoi_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:incoming-call-remix" {...props}></Icon>
