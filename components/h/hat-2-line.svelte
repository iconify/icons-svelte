<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drbstn8ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drbstn8ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hat-2-line" {...props}></Icon>
