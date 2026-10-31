<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psjqb7bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psjqb7bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-check-fill-round" {...props}></Icon>
