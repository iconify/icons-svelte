<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrwh4xbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrwh4xbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:copyright" {...props}></Icon>
