<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nujts8b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nujts8b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-half-line" {...props}></Icon>
