<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab9qd1foj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="ab9qd1foj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-small-right" {...props}></Icon>
