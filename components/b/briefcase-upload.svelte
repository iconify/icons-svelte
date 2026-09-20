<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t16rme36m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t16rme36m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-upload" {...props}></Icon>
