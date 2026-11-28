<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7qva2z3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7qva2z3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-text-plus" {...props}></Icon>
