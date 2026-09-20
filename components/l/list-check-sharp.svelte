<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf5xyob1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf5xyob1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-check-sharp" {...props}></Icon>
