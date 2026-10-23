<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgej2kbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hgej2kbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-que-merge-agent-16" {...props}></Icon>
