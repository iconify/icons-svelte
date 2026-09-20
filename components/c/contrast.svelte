<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0o9-ebpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g0o9-ebpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:contrast" {...props}></Icon>
