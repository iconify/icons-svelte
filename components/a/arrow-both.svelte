<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbvihdspj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="mbvihdspj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-both" {...props}></Icon>
