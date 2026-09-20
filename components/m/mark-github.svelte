<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doxlwt5no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="doxlwt5no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mark-github" {...props}></Icon>
