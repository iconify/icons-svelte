<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a24yiwbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a24yiwbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:anchor" {...props}></Icon>
