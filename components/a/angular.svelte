<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjhvk6baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjhvk6baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:angular" {...props}></Icon>
