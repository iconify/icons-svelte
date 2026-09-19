<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6qqfdbqz.css';
import '../../css/t/tsepx-fqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f6qqfdbqz"/><path class="tsepx-fqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:review" {...props}></Icon>
