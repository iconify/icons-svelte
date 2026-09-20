<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt-z4oblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt-z4oblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:password-solid" {...props}></Icon>
