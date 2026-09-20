<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odj9mk72t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="odj9mk72t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:package" {...props}></Icon>
