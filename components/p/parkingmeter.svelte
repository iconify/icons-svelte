<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_gcnebof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="h_gcnebof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:parkingmeter" {...props}></Icon>
