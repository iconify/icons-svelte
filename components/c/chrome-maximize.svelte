<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dye3ul6kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dye3ul6kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chrome-maximize" {...props}></Icon>
