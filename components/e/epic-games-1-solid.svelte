<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3sfjifiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r3sfjifiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:epic-games-1-solid" {...props}></Icon>
