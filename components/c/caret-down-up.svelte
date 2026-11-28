<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxi8rbh_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="oxi8rbh_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:caret-down-up" {...props}></Icon>
