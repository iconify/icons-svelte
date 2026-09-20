<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u530itbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u530itbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notion-line" {...props}></Icon>
