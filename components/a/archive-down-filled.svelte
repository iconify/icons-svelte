<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iozzqd6ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iozzqd6ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive-down-filled" {...props}></Icon>
