<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htnf9rifb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":6,"height":16};
const content = `<path class="htnf9rifb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-small-down" {...props}></Icon>
