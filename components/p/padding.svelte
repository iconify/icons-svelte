<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh09se2-w.css';
import '../../css/d/d-u2lgcch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bh09se2-w"/><path class="d-u2lgcch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:padding" {...props}></Icon>
