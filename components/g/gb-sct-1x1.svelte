<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdgac_b5a.css';
import '../../css/b/bf6u4_bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdgac_b5a"/><path transform="scale(102.4 170.66667)" class="bf6u4_bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:gb-sct-1x1" {...props}></Icon>
