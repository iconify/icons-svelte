<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t21s9b0zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t21s9b0zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-tika-binary-light" {...props}></Icon>
