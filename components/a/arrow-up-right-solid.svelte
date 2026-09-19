<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcwyqgoyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vcwyqgoyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-right-solid" {...props}></Icon>
