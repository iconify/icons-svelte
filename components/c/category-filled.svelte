<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv7_whsec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv7_whsec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:category-filled" {...props}></Icon>
