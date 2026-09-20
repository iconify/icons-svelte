<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm9egmo0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vm9egmo0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:redo" {...props}></Icon>
