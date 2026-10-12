<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rji5-yomq.css';
import '../../css/o/o1xu07rok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rji5-yomq"/><path class="o1xu07rok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-zip-fill-20" {...props}></Icon>
