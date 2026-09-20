<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzbc27bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tzbc27bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:loaf-of-bread-with-steam" {...props}></Icon>
