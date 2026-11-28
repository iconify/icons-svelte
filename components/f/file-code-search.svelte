<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvpm2nboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvpm2nboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-code-search" {...props}></Icon>
