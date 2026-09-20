<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xri8-yvdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xri8-yvdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:question-o" {...props}></Icon>
