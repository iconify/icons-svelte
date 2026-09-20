<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-0e6zbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n-0e6zbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:circle-filled" {...props}></Icon>
