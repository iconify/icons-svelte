<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t37m8-r3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t37m8-r3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:release-gate-check" {...props}></Icon>
