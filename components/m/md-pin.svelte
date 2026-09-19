<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-9123c1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-9123c1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pin" {...props}></Icon>
