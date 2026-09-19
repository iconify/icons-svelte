<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx9z7-b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx9z7-b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pen-alt" {...props}></Icon>
