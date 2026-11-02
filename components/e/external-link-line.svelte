<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl-3lebda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-3lebda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:external-link-line" {...props}></Icon>
