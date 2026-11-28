<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbd8do5tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbd8do5tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pilcrow-left-solid" {...props}></Icon>
