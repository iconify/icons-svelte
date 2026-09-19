<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al3802bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="al3802bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:roadmap" {...props}></Icon>
