<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzicu7o9n.css';
import '../../css/o/o962okb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jzicu7o9n"/><path class="o962okb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-images-open" {...props}></Icon>
