<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_9zuben.css';
import '../../css/g/g0ffiyboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vd_9zuben"/><path class="g0ffiyboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ellipsis-circle-o" {...props}></Icon>
