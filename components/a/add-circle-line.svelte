<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh0i2rbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh0i2rbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-circle-line" {...props}></Icon>
