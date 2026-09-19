<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqpf2n-tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="aqpf2n-tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:circle" {...props}></Icon>
