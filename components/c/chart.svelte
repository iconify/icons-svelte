<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytn98r1le.css';
import '../../css/h/hijr5tbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ytn98r1le"/><path class="hijr5tbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chart" {...props}></Icon>
