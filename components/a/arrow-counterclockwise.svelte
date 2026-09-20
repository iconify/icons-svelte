<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipg4k0btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipg4k0btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-counterclockwise" {...props}></Icon>
