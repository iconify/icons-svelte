<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmo-e9byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="hmo-e9byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:milestone" {...props}></Icon>
