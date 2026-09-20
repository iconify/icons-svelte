<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1iwlptgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="r1iwlptgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:machine-b-filled" {...props}></Icon>
