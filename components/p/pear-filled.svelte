<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uno_xbqqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uno_xbqqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pear-filled" {...props}></Icon>
