<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm78aw60m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sm78aw60m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:d-caret" {...props}></Icon>
