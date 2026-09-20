<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-zbukb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m-zbukb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sliding-down-cliff" {...props}></Icon>
