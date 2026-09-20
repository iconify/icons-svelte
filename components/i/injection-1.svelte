<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ertx3q4fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="ertx3q4fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:injection-1" {...props}></Icon>
