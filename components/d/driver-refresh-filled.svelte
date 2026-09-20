<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syr6mpbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syr6mpbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:driver-refresh-filled" {...props}></Icon>
