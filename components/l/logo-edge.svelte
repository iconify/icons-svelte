<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai3xiq51b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ai3xiq51b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-edge" {...props}></Icon>
