<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u22x8cbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u22x8cbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:citation" {...props}></Icon>
