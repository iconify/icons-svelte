<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqqep2yzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hqqep2yzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-15" {...props}></Icon>
