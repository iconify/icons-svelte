<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn35m6bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn35m6bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dhlpaket" {...props}></Icon>
