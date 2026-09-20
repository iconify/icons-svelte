<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axwlv8_bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axwlv8_bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart5-filled" {...props}></Icon>
