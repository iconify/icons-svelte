<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr8m7obju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nr8m7obju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:plan-view" {...props}></Icon>
