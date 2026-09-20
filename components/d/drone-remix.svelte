<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6c7vbb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v6c7vbb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:drone-remix" {...props}></Icon>
