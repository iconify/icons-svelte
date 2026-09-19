<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgygprbzp.css';
import '../../css/n/nkbsn0brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mgygprbzp"/><path class="nkbsn0brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:edit-undo-fill-12" {...props}></Icon>
