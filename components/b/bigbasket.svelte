<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbuy38iwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbuy38iwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bigbasket" {...props}></Icon>
