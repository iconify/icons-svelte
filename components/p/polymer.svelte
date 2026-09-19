<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prkc-3yml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":384};
const content = `<path class="prkc-3yml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:polymer" {...props}></Icon>
