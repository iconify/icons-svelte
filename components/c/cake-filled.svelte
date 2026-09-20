<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cze7y0brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cze7y0brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cake-filled" {...props}></Icon>
