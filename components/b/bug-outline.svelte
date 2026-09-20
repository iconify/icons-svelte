<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcn2ntb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcn2ntb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bug-outline" {...props}></Icon>
