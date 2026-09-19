<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nucobebyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nucobebyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:resize" {...props}></Icon>
