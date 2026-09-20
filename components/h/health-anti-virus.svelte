<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac3vaqbce.css';
import '../../css/r/rf8gf5fko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ac3vaqbce"/><path class="rf8gf5fko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-anti-virus" {...props}></Icon>
