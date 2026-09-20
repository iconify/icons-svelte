<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygklhwc9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygklhwc9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:eyedropper-color" {...props}></Icon>
