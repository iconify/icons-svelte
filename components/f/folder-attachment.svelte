<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-ad0g2qb.css';
import '../../css/o/ohmw5nbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l-ad0g2qb"/><path class="ohmw5nbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-attachment" {...props}></Icon>
