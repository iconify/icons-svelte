<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbbjl8juq.css';
import '../../css/h/hlgv9qbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wbbjl8juq"/><path class="hlgv9qbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-prisma" {...props}></Icon>
