<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvxp1d9fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hvxp1d9fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:home-2-remix" {...props}></Icon>
