<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8cc9ke3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="u8cc9ke3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:padlock" {...props}></Icon>
