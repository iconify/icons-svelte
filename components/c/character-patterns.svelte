<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dimqj2ncr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dimqj2ncr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:character-patterns" {...props}></Icon>
