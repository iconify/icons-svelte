<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7ijr0lpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k7ijr0lpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:jump-alt" {...props}></Icon>
