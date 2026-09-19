<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx9dqebgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kx9dqebgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:abap" {...props}></Icon>
