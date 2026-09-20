<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyi3bcceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyi3bcceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-top-fill" {...props}></Icon>
