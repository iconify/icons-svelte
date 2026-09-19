<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmnsknblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":424};
const content = `<path class="dmnsknblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:language-python-alt" {...props}></Icon>
