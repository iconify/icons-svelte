<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyu939b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vyu939b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jira" {...props}></Icon>
