<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-nz76glx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-nz76glx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:plus" {...props}></Icon>
