<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lahr7gp7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lahr7gp7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-minimalistic-linear" {...props}></Icon>
