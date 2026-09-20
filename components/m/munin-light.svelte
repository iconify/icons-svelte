<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw82aw3si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aw82aw3si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:munin-light" {...props}></Icon>
