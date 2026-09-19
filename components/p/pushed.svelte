<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qerf4abpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="qerf4abpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:pushed" {...props}></Icon>
