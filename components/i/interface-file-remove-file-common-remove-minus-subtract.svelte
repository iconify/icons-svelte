<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd89idvdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xd89idvdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-file-remove-file-common-remove-minus-subtract" {...props}></Icon>
