<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l46lvfrxi.css';
import '../../css/g/g07kyqb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l46lvfrxi"/><path class="g07kyqb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-zip-stroke-20" {...props}></Icon>
