<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfm7f3bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfm7f3bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rewind-circle-solid" {...props}></Icon>
