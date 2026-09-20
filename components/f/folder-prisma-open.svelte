<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu9ugknqy.css';
import '../../css/h/hlgv9qbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wu9ugknqy"/><path class="hlgv9qbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-prisma-open" {...props}></Icon>
