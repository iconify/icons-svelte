<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hig-594lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hig-594lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-2-filled" {...props}></Icon>
