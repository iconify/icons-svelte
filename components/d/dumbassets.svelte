<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j29moabpi.css';
import '../../css/e/etvlrmq6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="j29moabpi"/><path class="etvlrmq6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbassets" {...props}></Icon>
