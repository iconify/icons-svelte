<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-y1abmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4-y1abmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bazarr" {...props}></Icon>
