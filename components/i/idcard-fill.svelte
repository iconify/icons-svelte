<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d52xo5bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d52xo5bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:idcard-fill" {...props}></Icon>
