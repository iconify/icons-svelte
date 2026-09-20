<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv666bbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv666bbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:building-4-line" {...props}></Icon>
