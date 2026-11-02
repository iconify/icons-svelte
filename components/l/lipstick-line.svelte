<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go02y2lxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go02y2lxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lipstick-line" {...props}></Icon>
