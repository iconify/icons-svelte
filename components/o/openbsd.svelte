<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ek6sqpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_ek6sqpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openbsd" {...props}></Icon>
