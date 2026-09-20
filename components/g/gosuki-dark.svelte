<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bodxe5byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bodxe5byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gosuki-dark" {...props}></Icon>
