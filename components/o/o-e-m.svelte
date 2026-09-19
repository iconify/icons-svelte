<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhcbccc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rhcbccc9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:o-e-m" {...props}></Icon>
