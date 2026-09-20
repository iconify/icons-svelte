<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udzq6tb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udzq6tb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:call-off" {...props}></Icon>
