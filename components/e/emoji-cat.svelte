<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1a1f6wsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1a1f6wsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-cat" {...props}></Icon>
