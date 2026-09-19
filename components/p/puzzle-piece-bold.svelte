<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg1s3861r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":83,"height":82};
const content = `<path clip-rule="evenodd" class="rg1s3861r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:puzzle-piece-bold" {...props}></Icon>
