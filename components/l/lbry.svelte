<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo-d3i9sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-d3i9sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lbry" {...props}></Icon>
