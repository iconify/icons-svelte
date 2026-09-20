<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzi3s0umo.css';
import '../../css/k/kz83e19cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rzi3s0umo"/><path class="kz83e19cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-hierarchy-files" {...props}></Icon>
