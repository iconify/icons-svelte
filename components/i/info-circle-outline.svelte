<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upv0h93hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upv0h93hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:info-circle-outline" {...props}></Icon>
