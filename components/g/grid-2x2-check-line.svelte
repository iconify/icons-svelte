<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djl89ku6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djl89ku6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grid-2x2-check-line" {...props}></Icon>
