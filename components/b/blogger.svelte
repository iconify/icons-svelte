<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg6wskbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="dg6wskbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:blogger" {...props}></Icon>
