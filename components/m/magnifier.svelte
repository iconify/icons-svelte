<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zimqkib2m.css';
import '../../css/y/y1jfbyb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zimqkib2m"/><path class="y1jfbyb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:magnifier" {...props}></Icon>
