<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d771kzbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="d771kzbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:box-rect" {...props}></Icon>
