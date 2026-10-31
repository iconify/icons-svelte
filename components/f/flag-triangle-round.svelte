<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phr3gzdys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phr3gzdys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-triangle-round" {...props}></Icon>
