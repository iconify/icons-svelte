<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o36_d_eac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o36_d_eac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add" {...props}></Icon>
