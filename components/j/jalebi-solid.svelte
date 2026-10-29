<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvphuy7cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvphuy7cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:jalebi-solid" {...props}></Icon>
