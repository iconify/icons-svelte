<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byhf100bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byhf100bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:code-check" {...props}></Icon>
