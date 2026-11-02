<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpay0fb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpay0fb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lungs-line" {...props}></Icon>
