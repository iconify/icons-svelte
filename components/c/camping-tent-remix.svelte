<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eieyf_ezi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eieyf_ezi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:camping-tent-remix" {...props}></Icon>
