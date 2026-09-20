<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ym0rb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="l1ym0rb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:brush-1-rotated" {...props}></Icon>
