<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va3pt_bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="va3pt_bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cloud" {...props}></Icon>
