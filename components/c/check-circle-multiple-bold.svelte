<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgee6ac_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tgee6ac_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:check-circle-multiple-bold" {...props}></Icon>
