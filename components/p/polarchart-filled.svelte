<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4-h6-tbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g4-h6-tbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:polarchart-filled" {...props}></Icon>
