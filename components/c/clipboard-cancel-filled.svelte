<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1p_8cbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1p_8cbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-cancel-filled" {...props}></Icon>
