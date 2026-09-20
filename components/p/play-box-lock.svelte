<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ye_xbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ye_xbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-lock" {...props}></Icon>
