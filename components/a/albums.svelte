<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mayialn-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mayialn-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:albums" {...props}></Icon>
