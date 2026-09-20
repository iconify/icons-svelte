<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdam21bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdam21bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:focus-fill" {...props}></Icon>
