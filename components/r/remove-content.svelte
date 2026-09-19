<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so4ehfbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="so4ehfbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:remove-content" {...props}></Icon>
