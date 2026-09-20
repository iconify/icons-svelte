<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwhnshbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwhnshbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:collapse" {...props}></Icon>
