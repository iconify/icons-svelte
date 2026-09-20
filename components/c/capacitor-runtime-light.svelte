<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwuw72bhz.css';
import '../../css/g/gs0icwbbh.css';
import '../../css/e/ebf9xob5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gwuw72bhz"/><path class="gs0icwbbh"/><path class="ebf9xob5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:capacitor-runtime-light" {...props}></Icon>
