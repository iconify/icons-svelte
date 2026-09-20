<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trp5kebab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trp5kebab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:doc-line" {...props}></Icon>
