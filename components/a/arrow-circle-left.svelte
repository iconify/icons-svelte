<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p89tr8rsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p89tr8rsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-circle-left" {...props}></Icon>
