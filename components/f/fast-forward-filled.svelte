<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh5ri3jtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uh5ri3jtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:fast-forward-filled" {...props}></Icon>
