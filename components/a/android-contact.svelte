<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amezjz6vh.css';
import '../../css/a/a1eidib9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amezjz6vh"/><path class="a1eidib9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-contact" {...props}></Icon>
