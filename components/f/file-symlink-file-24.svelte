<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3r5-6bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3r5-6bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-symlink-file-24" {...props}></Icon>
