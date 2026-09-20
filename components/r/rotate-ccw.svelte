<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt_4kcc7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt_4kcc7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rotate-ccw" {...props}></Icon>
