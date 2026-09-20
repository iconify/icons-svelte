<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3ytlbiz.css';
import '../../css/d/dlp46-bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rw3ytlbiz"/><path class="dlp46-bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:progressbar" {...props}></Icon>
