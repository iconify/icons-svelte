<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1wi_jbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j1wi_jbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pencil-16" {...props}></Icon>
