<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx2kyvb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tx2kyvb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:bluetooth" {...props}></Icon>
