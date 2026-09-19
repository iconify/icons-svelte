<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka74e-dqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ka74e-dqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:filter-outline" {...props}></Icon>
