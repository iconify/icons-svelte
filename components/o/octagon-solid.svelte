<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vww_86bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vww_86bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:octagon-solid" {...props}></Icon>
