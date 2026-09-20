<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ciceb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8ciceb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:letter-spacing-line" {...props}></Icon>
