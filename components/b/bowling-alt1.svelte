<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwn4y6b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="nwn4y6b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bowling-alt1" {...props}></Icon>
