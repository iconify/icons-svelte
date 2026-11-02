<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8bxy215p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8bxy215p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grape-line" {...props}></Icon>
