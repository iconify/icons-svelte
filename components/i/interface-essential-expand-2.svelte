<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b40784e-u.css';
import '../../css/g/g7_--dwga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b40784e-u"/><path class="g7_--dwga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-expand-2" {...props}></Icon>
