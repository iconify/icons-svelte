<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y937k6bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y937k6bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-down-fill" {...props}></Icon>
