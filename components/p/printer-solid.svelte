<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y20u0nbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y20u0nbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:printer-solid" {...props}></Icon>
