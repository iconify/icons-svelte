<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2cfpnpgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f2cfpnpgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bubble-right" {...props}></Icon>
