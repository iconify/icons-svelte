<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6s4wib7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="a6s4wib7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flower" {...props}></Icon>
