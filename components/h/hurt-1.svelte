<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkfyo6bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dkfyo6bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:hurt-1" {...props}></Icon>
