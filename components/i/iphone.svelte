<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/memx0ebgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":512};
const content = `<path class="memx0ebgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:iphone" {...props}></Icon>
