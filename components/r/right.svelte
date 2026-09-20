<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0x476ygt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a0x476ygt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:right" {...props}></Icon>
