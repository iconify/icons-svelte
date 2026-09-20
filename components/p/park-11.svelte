<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1hcn6bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="l1hcn6bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:park-11" {...props}></Icon>
