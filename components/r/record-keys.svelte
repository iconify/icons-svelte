<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt9nc3b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wt9nc3b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:record-keys" {...props}></Icon>
