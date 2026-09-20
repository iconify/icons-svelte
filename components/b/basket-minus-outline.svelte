<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwf3d0p4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gwf3d0p4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:basket-minus-outline" {...props}></Icon>
