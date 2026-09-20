<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgj_o_0ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="bgj_o_0ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:license-sm" {...props}></Icon>
