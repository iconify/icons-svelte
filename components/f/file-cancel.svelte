<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vitt06svn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vitt06svn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-cancel" {...props}></Icon>
