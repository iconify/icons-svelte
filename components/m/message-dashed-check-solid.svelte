<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj3idy5_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj3idy5_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-dashed-check-solid" {...props}></Icon>
