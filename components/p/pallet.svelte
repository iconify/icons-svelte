<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v82j94bfo.css';
import '../../css/d/dgp4q7bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v82j94bfo"/><path class="dgp4q7bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pallet" {...props}></Icon>
