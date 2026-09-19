<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc3492_1p.css';
import '../../css/b/bud9nuiqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qc3492_1p"/><path class="bud9nuiqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:promote" {...props}></Icon>
