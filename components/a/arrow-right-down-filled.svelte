<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn3zzekcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn3zzekcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-down-filled" {...props}></Icon>
