<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6m821bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v6m821bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:michigan" {...props}></Icon>
