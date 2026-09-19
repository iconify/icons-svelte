<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8wp0nbtd.css';
import '../../css/m/m5ioxlbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8wp0nbtd"/><path class="m5ioxlbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-file" {...props}></Icon>
