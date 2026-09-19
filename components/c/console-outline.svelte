<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg52a2w4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg52a2w4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:console-outline" {...props}></Icon>
