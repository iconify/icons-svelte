<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c93y5pb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c93y5pb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:focus-solid" {...props}></Icon>
