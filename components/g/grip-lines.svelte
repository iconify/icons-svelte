<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywd6cmbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ywd6cmbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:grip-lines" {...props}></Icon>
