<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duf9j9bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="duf9j9bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gmail-remix" {...props}></Icon>
