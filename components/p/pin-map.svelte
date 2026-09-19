<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9prg-o0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":528};
const content = `<path class="v9prg-o0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pin-map" {...props}></Icon>
