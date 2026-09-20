<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nklcr7bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nklcr7bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-line" {...props}></Icon>
