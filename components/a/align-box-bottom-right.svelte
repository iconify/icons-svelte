<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxn06vble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxn06vble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-bottom-right" {...props}></Icon>
