<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgjpb0q-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hgjpb0q-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-arrow-up-right-arrow-down-left" {...props}></Icon>
