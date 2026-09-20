<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_aarwbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="o_aarwbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:lamp" {...props}></Icon>
