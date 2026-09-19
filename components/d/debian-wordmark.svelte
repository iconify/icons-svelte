<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ll3kbae.css';
import '../../css/i/iyzk2db_h.css';
import '../../css/i/iwengkb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t3ll3kbae"/><path class="iyzk2db_h"/><path class="iwengkb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:debian-wordmark" {...props}></Icon>
