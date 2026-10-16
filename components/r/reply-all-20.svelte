<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccnyeob1g.css';
import '../../css/i/i3bujsneb.css';
import '../../css/m/mccycacnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ccnyeob1g"/><path class="i3bujsneb"/><path class="mccycacnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reply-all-20" {...props}></Icon>
