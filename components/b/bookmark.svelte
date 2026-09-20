<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2oma5ksy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g2oma5ksy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bookmark" {...props}></Icon>
