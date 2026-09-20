<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvcue3bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvcue3bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-lanscape-slash" {...props}></Icon>
