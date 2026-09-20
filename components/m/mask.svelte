<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aie3zsbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aie3zsbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mask" {...props}></Icon>
