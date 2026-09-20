<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdnyquupd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdnyquupd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:replace-off" {...props}></Icon>
