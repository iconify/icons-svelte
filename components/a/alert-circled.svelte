<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_tzv3i3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_tzv3i3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:alert-circled" {...props}></Icon>
