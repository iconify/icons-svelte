<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za6ahqbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za6ahqbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-x-corner-line" {...props}></Icon>
