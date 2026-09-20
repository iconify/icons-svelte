<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyqo3cbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyqo3cbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:align-alt" {...props}></Icon>
