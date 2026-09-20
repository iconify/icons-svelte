<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw3q26qvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw3q26qvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:myna-solid" {...props}></Icon>
