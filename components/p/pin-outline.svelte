<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4205ac_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4205ac_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-outline" {...props}></Icon>
