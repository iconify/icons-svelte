<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc3_7sb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mc3_7sb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:compass" {...props}></Icon>
