<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf3zqez6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cf3zqez6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:hangup" {...props}></Icon>
