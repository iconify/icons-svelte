<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldfk44b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ldfk44b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:mountain-cross" {...props}></Icon>
