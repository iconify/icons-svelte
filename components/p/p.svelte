<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_e83v4za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1408};
const content = `<path class="o_e83v4za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:p" {...props}></Icon>
