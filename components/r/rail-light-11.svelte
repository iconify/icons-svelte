<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iboduub-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="iboduub-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:rail-light-11" {...props}></Icon>
