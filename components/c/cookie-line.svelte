<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6s45cn0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6s45cn0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cookie-line" {...props}></Icon>
