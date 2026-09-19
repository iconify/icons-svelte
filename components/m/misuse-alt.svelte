<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd42r404p.css';
import '../../css/k/kigsbgfya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cd42r404p"/><path class="kigsbgfya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:misuse-alt" {...props}></Icon>
