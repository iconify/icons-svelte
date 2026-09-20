<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ura6pn2-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ura6pn2-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mouse" {...props}></Icon>
