<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm3r0-bhi.css';
import '../../css/p/pyjnocccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wm3r0-bhi"/><path clip-rule="evenodd" class="pyjnocccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:heart-crossed-16" {...props}></Icon>
