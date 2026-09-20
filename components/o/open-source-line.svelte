<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr3w9-lmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr3w9-lmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:open-source-line" {...props}></Icon>
