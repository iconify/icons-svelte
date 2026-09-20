<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzicu7o9n.css';
import '../../css/k/knky5hmzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jzicu7o9n"/><path class="knky5hmzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-organism-open" {...props}></Icon>
