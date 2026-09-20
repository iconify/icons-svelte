<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jziryxb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jziryxb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:accessibility" {...props}></Icon>
