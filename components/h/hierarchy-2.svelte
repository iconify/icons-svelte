<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueipv7ldy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ueipv7ldy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-2" {...props}></Icon>
