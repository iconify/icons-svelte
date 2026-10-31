<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-uo8pvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf-uo8pvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-code-round" {...props}></Icon>
