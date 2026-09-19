<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7d6iacxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s7d6iacxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:no-one-under-eighteen-symbol" {...props}></Icon>
