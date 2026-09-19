<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrsh7gb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="xrsh7gb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:archive" {...props}></Icon>
