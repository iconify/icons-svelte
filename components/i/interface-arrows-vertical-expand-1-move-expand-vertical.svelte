<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vspa-mbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vspa-mbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-vertical-expand-1-move-expand-vertical" {...props}></Icon>
