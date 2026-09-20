<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3hoi0mvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3hoi0mvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-check-line" {...props}></Icon>
