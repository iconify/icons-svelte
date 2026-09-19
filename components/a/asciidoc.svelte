<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u11ifk20b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":439,"height":512};
const content = `<path class="u11ifk20b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:asciidoc" {...props}></Icon>
