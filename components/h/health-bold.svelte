<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/capkmo5jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="capkmo5jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:health-bold" {...props}></Icon>
