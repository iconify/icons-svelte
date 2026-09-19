<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu1u2abpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="eu1u2abpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-circle" {...props}></Icon>
