<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orw8s647j.css';
import '../../css/f/fwvo6n8hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="orw8s647j"/><path class="fwvo6n8hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:filter-edit" {...props}></Icon>
