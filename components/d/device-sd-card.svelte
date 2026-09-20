<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_qc3pzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_qc3pzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-sd-card" {...props}></Icon>
