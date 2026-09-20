<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh1hauwkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vh1hauwkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:menu-unfold" {...props}></Icon>
