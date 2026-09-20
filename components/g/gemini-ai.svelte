<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpbd8hs9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zpbd8hs9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gemini-ai" {...props}></Icon>
