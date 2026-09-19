<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj7n3bbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="qj7n3bbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:caret-circle-bold" {...props}></Icon>
