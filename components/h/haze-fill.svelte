<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s23ly6bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s23ly6bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:haze-fill" {...props}></Icon>
