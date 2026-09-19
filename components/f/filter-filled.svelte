<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gna7bpbhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gna7bpbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:filter-filled" {...props}></Icon>
