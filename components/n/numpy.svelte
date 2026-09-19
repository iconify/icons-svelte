<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qslq46b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="qslq46b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:numpy" {...props}></Icon>
