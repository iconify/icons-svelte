<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdie0hb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mdie0hb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:plus-solid" {...props}></Icon>
