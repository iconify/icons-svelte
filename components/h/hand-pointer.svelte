<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9bht_bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x9bht_bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:hand-pointer" {...props}></Icon>
