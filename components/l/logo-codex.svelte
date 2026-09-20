<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz32hfa-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dz32hfa-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:logo-codex" {...props}></Icon>
