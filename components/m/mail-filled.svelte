<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye28mvbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ye28mvbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mail-filled" {...props}></Icon>
