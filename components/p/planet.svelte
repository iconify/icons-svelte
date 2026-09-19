<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv2cl-bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":641};
const content = `<path class="gv2cl-bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:planet" {...props}></Icon>
