<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzxe0-1un.css';
import '../../css/h/h84axl_8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zzxe0-1un"/><path class="h84axl_8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:djangorest-wordmark" {...props}></Icon>
