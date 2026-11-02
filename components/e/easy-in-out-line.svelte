<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_e2u0buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_e2u0buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:easy-in-out-line" {...props}></Icon>
