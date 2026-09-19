<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqb-30dti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wqb-30dti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:beaker" {...props}></Icon>
