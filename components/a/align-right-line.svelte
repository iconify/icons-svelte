<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2obbm2nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2obbm2nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-right-line" {...props}></Icon>
