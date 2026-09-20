<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx4ddcyzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx4ddcyzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-zip-filled" {...props}></Icon>
