<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljw_bfb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljw_bfb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-check-solid" {...props}></Icon>
