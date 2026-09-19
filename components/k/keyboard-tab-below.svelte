<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwl893x-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dwl893x-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:keyboard-tab-below" {...props}></Icon>
