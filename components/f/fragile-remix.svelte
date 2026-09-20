<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjjm0f90s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cjjm0f90s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fragile-remix" {...props}></Icon>
