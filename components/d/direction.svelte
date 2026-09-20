<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4x64lg8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="n4x64lg8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:direction" {...props}></Icon>
