<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roiy15max.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="roiy15max"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:full-screen-osx-remix" {...props}></Icon>
