<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r60vhccip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="r60vhccip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dumbbell" {...props}></Icon>
