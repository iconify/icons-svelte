<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj29iu_gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sj29iu_gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:redo" {...props}></Icon>
