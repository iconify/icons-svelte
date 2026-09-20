<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-h01obyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-h01obyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:battery-filled" {...props}></Icon>
