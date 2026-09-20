<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjcj41b6z.css';
import '../../css/l/l-n55zbgm.css';
import '../../css/a/a79pf1bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjcj41b6z"/><path class="l-n55zbgm"/><path class="a79pf1bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-docs" {...props}></Icon>
