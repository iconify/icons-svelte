<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx__e5bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xx__e5bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:emoji-funny-square-bold" {...props}></Icon>
