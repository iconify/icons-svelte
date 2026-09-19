<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-2ahia8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":32};
const content = `<path class="t-2ahia8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:paperclip" {...props}></Icon>
