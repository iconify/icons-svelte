<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w14fwxg9c.css';
import '../../css/p/p9upddc0f.css';
import '../../css/o/o7tfrmnak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w14fwxg9c"/><path class="p9upddc0f"/><path class="o7tfrmnak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:operation-if" {...props}></Icon>
