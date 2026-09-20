<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4oh6vw-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="v4oh6vw-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-right" {...props}></Icon>
