<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txxrw9wmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-4};
const content = `<path class="txxrw9wmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:move-alt" {...props}></Icon>
