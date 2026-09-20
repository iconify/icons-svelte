<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy4rl4bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vy4rl4bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:inbox-outline" {...props}></Icon>
