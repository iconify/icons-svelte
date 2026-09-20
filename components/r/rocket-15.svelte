<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btf34qj2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="btf34qj2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:rocket-15" {...props}></Icon>
