<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enat21b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enat21b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:drop-line" {...props}></Icon>
