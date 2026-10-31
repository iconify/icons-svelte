<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_1nhdbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_1nhdbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-warning-fill-round" {...props}></Icon>
